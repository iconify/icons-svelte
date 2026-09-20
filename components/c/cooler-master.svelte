<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxg0005bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxg0005bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cooler-master" {...props}></Icon>
