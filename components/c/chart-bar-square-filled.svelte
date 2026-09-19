<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abbv8_b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abbv8_b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-bar-square-filled" {...props}></Icon>
