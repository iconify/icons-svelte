<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4i-8mbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4i-8mbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:font-size-ai" {...props}></Icon>
