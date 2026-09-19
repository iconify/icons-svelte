<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cosz63sab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="cosz63sab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:hotel" {...props}></Icon>
