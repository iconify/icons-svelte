<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb759fl4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb759fl4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:magnet-up" {...props}></Icon>
