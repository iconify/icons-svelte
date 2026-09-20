<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdz4gjb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdz4gjb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nordic-walking" {...props}></Icon>
