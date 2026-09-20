<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpl5qy6cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpl5qy6cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-brl" {...props}></Icon>
