<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfy7r0byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfy7r0byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fossil-fuel" {...props}></Icon>
