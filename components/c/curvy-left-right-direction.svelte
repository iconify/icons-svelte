<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxi3aebem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxi3aebem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:curvy-left-right-direction" {...props}></Icon>
