<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fae5gbciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fae5gbciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-download-fill" {...props}></Icon>
