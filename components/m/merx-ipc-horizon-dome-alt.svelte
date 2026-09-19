<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu8hkab6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu8hkab6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:merx-ipc-horizon-dome-alt" {...props}></Icon>
