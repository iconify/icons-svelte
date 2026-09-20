<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa1_z_ayb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa1_z_ayb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:repeat-one-line" {...props}></Icon>
