<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we2rg-n4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we2rg-n4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-down-left" {...props}></Icon>
