<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpzcypbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="wpzcypbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:plug-1" {...props}></Icon>
