<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usitz_vjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usitz_vjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:clapperboard-play-outline" {...props}></Icon>
