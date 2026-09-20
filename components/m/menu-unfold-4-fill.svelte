<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwd01r-qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwd01r-qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-unfold-4-fill" {...props}></Icon>
