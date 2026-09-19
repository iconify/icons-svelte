<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pldvvq-vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pldvvq-vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:floor-lantern-group" {...props}></Icon>
