<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q76ry8bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="q76ry8bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:cloud-upload-alt" {...props}></Icon>
