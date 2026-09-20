<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajjghacij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajjghacij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-plug" {...props}></Icon>
