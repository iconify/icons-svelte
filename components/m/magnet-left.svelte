<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky8l_-t4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky8l_-t4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:magnet-left" {...props}></Icon>
