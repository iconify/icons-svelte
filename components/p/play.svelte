<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyt0_tamv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyt0_tamv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:play" {...props}></Icon>
