<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxrdtcc_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxrdtcc_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ovhcloud" {...props}></Icon>
