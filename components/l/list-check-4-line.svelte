<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc0h5zb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc0h5zb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-4-line" {...props}></Icon>
