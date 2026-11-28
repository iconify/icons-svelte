<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay049ub1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay049ub1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:heart-check" {...props}></Icon>
