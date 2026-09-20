<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-di8ibbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-di8ibbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:home-smile-solid" {...props}></Icon>
