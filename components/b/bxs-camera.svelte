<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlcke6kyc.css';
import '../../css/r/r4v-mt3za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlcke6kyc"/><path class="r4v-mt3za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-camera" {...props}></Icon>
