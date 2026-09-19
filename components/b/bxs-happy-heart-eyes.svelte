<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmpf0vbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmpf0vbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-happy-heart-eyes" {...props}></Icon>
