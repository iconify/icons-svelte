<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d50_phb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d50_phb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-poop" {...props}></Icon>
