<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idxndm8dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idxndm8dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:exclamation-triangle" {...props}></Icon>
