<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av-ff1z_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av-ff1z_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:prestashop" {...props}></Icon>
