<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wloq5pbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wloq5pbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-negative-1" {...props}></Icon>
