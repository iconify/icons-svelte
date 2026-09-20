<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3x0uu0wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3x0uu0wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-usd-off" {...props}></Icon>
