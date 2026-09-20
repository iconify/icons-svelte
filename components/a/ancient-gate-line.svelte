<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_l8gwbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_l8gwbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ancient-gate-line" {...props}></Icon>
