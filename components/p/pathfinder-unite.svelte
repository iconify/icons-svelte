<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj8kszbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj8kszbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:pathfinder-unite" {...props}></Icon>
