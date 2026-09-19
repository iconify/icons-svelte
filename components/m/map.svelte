<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0dav7bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":637};
const content = `<path class="y0dav7bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:map" {...props}></Icon>
