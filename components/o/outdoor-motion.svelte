<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2b-a_j-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2b-a_j-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:outdoor-motion" {...props}></Icon>
