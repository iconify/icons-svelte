<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2shq74qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2shq74qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-column-decreasing" {...props}></Icon>
