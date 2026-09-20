<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p333-tb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p333-tb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:atm" {...props}></Icon>
