<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oag5zrlby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oag5zrlby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:decimals-arrow-left" {...props}></Icon>
