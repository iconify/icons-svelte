<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9xn-jbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9xn-jbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:headphones-off-outline" {...props}></Icon>
