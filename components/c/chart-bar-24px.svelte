<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvdy0ubkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvdy0ubkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-bar-24px" {...props}></Icon>
