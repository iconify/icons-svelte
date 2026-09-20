<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_jc7nyzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n_jc7nyzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:plugin" {...props}></Icon>
