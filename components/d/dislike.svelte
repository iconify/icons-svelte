<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mie05o1hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mie05o1hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:dislike" {...props}></Icon>
