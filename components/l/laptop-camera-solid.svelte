<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq8v6ibzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iq8v6ibzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:laptop-camera-solid" {...props}></Icon>
