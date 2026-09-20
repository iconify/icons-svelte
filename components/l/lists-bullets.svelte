<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsif9abwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsif9abwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:lists-bullets" {...props}></Icon>
