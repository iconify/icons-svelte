<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zia8m971p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zia8m971p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-maintenance" {...props}></Icon>
