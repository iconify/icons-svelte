<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-trz4bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-trz4bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cloud-wifi-solid" {...props}></Icon>
