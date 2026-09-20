<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlnf2iwfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlnf2iwfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nic" {...props}></Icon>
