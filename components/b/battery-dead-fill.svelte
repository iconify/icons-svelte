<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rty2h_9ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rty2h_9ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:battery-dead-fill" {...props}></Icon>
