<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phsxt4blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phsxt4blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bitcoin" {...props}></Icon>
