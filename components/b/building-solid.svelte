<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1j6fbb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1j6fbb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:building-solid" {...props}></Icon>
