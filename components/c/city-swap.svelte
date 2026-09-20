<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqmk94bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqmk94bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:city-swap" {...props}></Icon>
