<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydmm0mbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydmm0mbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:car-auto" {...props}></Icon>
