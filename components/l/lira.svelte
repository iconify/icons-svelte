<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wca9nwbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wca9nwbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:lira" {...props}></Icon>
