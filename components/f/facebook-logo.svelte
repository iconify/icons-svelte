<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpahoeb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vpahoeb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:facebook-logo" {...props}></Icon>
