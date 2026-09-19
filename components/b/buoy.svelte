<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdfhixbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdfhixbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:buoy" {...props}></Icon>
