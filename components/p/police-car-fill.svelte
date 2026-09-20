<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1hpkybtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1hpkybtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:police-car-fill" {...props}></Icon>
