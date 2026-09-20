<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef_187bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef_187bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-m-square-solid" {...props}></Icon>
