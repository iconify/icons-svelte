<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji5yl_z2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="ji5yl_z2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:like" {...props}></Icon>
