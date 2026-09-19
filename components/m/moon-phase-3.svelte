<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr6ahtbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr6ahtbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-3" {...props}></Icon>
