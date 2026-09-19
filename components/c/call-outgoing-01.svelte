<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnr_e_b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnr_e_b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-outgoing-01" {...props}></Icon>
