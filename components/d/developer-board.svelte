<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4z6z2bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4z6z2bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:developer-board" {...props}></Icon>
