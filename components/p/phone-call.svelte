<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6d5uggdo.css';
import '../../css/c/cuzgrrbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6d5uggdo"/><path class="cuzgrrbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:phone-call" {...props}></Icon>
