<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdkomdvjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdkomdvjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:blinds-closed" {...props}></Icon>
