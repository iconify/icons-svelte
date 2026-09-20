<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhoum_bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhoum_bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rolodex" {...props}></Icon>
