<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voh4ogz7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voh4ogz7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:passport-minus" {...props}></Icon>
