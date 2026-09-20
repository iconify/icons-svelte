<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqpln8bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqpln8bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-3-plus" {...props}></Icon>
