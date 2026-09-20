<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcq99_yio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcq99_yio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:battery-charging-fill" {...props}></Icon>
