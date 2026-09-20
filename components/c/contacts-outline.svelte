<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl324dpyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl324dpyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:contacts-outline" {...props}></Icon>
