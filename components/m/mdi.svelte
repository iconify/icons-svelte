<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi0x__bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi0x__bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mdi" {...props}></Icon>
