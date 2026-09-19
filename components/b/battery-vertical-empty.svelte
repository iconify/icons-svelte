<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx1mgel_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx1mgel_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:battery-vertical-empty" {...props}></Icon>
