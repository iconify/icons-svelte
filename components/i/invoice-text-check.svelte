<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvn8gabrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvn8gabrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-check" {...props}></Icon>
