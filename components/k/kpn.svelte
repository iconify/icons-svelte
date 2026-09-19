<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icnfy4vhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="icnfy4vhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:kpn" {...props}></Icon>
