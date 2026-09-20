<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj1hmv_zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj1hmv_zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:book-audio" {...props}></Icon>
