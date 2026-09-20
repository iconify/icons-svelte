<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m53qb4i-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m53qb4i-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dad" {...props}></Icon>
