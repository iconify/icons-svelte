<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsmvn1bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsmvn1bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:eco-house-remix" {...props}></Icon>
