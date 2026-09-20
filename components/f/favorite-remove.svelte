<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kntp21bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kntp21bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-remove" {...props}></Icon>
