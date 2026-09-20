<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4e2-rves.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4e2-rves"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:planet-box-plus" {...props}></Icon>
