<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m92zv-bjj.css';
import '../../css/h/h71b5fbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m92zv-bjj"/><path class="h71b5fbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-bold" {...props}></Icon>
