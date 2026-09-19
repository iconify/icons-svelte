<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs77xgrwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs77xgrwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:nav-arrow-up" {...props}></Icon>
