<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbboz65cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbboz65cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chrome-web-store" {...props}></Icon>
