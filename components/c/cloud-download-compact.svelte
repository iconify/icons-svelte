<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckxvtmlqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ckxvtmlqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:cloud-download-compact" {...props}></Icon>
