<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khpblbcpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khpblbcpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-left-3-filled" {...props}></Icon>
