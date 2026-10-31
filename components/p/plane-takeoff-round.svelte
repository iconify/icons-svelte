<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo1hrhboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo1hrhboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plane-takeoff-round" {...props}></Icon>
