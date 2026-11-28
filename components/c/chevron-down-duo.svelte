<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flp7q6biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flp7q6biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-down-duo" {...props}></Icon>
