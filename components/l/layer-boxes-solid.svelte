<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9ceq2bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9ceq2bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layer-boxes-solid" {...props}></Icon>
