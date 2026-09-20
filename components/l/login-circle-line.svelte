<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbsc4s31x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbsc4s31x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:login-circle-line" {...props}></Icon>
