<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr9efjb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr9efjb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:merx-ipc-horizon-dome" {...props}></Icon>
