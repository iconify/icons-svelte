<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whw6_eifb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whw6_eifb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:progress-question" {...props}></Icon>
