<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/merxirxax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="merxirxax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-box-middle-center" {...props}></Icon>
