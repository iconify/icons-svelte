<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuote0biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuote0biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lightning-2-bold" {...props}></Icon>
