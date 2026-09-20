<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk23wxppw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="zk23wxppw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:filter" {...props}></Icon>
