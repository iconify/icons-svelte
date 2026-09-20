<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujv1pcbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujv1pcbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-circle-perspective-counterclockwise-expressive" {...props}></Icon>
