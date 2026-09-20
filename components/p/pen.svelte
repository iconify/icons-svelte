<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh6k4491x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-3};
const content = `<path class="wh6k4491x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:pen" {...props}></Icon>
