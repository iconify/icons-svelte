<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yih6tez8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yih6tez8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:link-2" {...props}></Icon>
