<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnx5vacuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="qnx5vacuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plug-circle-check" {...props}></Icon>
