<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn8g8r50i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn8g8r50i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:currency-fill" {...props}></Icon>
