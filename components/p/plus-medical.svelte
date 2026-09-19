<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujwgymbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujwgymbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:plus-medical" {...props}></Icon>
