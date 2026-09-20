<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd2gdm8fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd2gdm8fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:indeterminate-check-box" {...props}></Icon>
