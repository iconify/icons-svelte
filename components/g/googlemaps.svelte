<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky3l1lb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky3l1lb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googlemaps" {...props}></Icon>
