<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c82udlbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c82udlbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:escalator-down-filled" {...props}></Icon>
