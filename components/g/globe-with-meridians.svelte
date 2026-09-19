<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4_utgbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="c4_utgbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:globe-with-meridians" {...props}></Icon>
