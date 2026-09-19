<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y84s00bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y84s00bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:currency-ruble" {...props}></Icon>
