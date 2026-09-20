<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4fwx8bcd.css';
import '../../css/k/kp9tsokzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4fwx8bcd"/><path class="kp9tsokzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:asd" {...props}></Icon>
