<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1ez_g0zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q1ez_g0zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:puzzle-duotone" {...props}></Icon>
