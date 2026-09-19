<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc8zf3buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc8zf3buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:filter-add" {...props}></Icon>
