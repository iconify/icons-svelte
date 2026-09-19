<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dctxs9-rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dctxs9-rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:binoculars" {...props}></Icon>
