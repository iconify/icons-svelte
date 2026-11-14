<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo96n54an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo96n54an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dollar-01" {...props}></Icon>
