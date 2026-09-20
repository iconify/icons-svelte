<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj2xip8kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="gj2xip8kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flame" {...props}></Icon>
