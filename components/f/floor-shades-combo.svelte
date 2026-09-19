<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uigpp6_gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uigpp6_gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:floor-shades-combo" {...props}></Icon>
