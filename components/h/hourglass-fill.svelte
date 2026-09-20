<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiruu6tbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qiruu6tbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hourglass-fill" {...props}></Icon>
