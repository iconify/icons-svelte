<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-j2tshyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h-j2tshyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:edit-solid-mirrored-12" {...props}></Icon>
