<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zep9gyb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zep9gyb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-left-square-solid" {...props}></Icon>
