<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0_-kgbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0_-kgbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-lock" {...props}></Icon>
