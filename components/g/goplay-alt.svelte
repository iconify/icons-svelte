<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shl10mbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shl10mbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:goplay-alt" {...props}></Icon>
