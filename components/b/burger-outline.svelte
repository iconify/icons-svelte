<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqew5hb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqew5hb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:burger-outline" {...props}></Icon>
