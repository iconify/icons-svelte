<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt6kbdbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt6kbdbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gatsby-line" {...props}></Icon>
