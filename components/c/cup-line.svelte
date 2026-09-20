<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvp-l7bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvp-l7bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:cup-line" {...props}></Icon>
