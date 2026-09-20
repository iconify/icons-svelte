<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc42srf3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc42srf3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airpods-fill" {...props}></Icon>
