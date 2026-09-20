<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct_bdfr0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct_bdfr0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:fire-fill" {...props}></Icon>
