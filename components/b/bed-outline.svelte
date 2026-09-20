<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhyhz9zwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhyhz9zwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bed-outline" {...props}></Icon>
