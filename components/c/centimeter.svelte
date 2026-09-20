<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu81sg07k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu81sg07k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:centimeter" {...props}></Icon>
