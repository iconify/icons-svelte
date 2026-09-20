<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd-tiu1yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd-tiu1yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:number-5" {...props}></Icon>
