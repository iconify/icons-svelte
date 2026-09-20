<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqlfl2olr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqlfl2olr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:font-size" {...props}></Icon>
