<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx9i_ms2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gx9i_ms2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:peach" {...props}></Icon>
