<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me2jhw4ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me2jhw4ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:office-building-minus-outline" {...props}></Icon>
