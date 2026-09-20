<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kghigabql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kghigabql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cheese-off" {...props}></Icon>
