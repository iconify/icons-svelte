<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyjq7qbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyjq7qbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:phoenix-plafond" {...props}></Icon>
