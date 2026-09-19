<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl-2c38wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl-2c38wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:beanie" {...props}></Icon>
