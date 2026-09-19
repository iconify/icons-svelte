<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ionb5zl4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ionb5zl4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-schedule" {...props}></Icon>
