<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfr_agb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yfr_agb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:map-pin-heart-fill" {...props}></Icon>
