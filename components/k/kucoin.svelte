<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyg9uzb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyg9uzb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kucoin" {...props}></Icon>
