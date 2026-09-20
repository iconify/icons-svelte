<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iabycjbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iabycjbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:globe-detailed-line" {...props}></Icon>
