<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbnmj0bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbnmj0bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-remove" {...props}></Icon>
