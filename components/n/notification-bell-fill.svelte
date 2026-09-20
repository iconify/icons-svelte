<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkul2mbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkul2mbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-fill" {...props}></Icon>
