<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq5q78n-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="sq5q78n-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-square-down-f" {...props}></Icon>
