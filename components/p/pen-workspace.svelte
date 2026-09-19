<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_5eprver.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="z_5eprver"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:pen-workspace" {...props}></Icon>
