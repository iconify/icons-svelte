<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6sq5sb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6sq5sb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:building3-filled" {...props}></Icon>
