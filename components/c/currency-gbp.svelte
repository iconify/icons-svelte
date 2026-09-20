<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f83ut6b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f83ut6b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-gbp" {...props}></Icon>
