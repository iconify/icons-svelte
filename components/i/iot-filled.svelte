<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7s8y0yps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k7s8y0yps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:iot-filled" {...props}></Icon>
