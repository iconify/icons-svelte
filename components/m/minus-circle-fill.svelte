<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfy5fyr1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfy5fyr1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:minus-circle-fill" {...props}></Icon>
