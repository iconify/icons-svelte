<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glp1ur27k.css';
import '../../css/w/ww5xev0qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glp1ur27k"/><path class="ww5xev0qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-pulse-2-bold" {...props}></Icon>
