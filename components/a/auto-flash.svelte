<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_qh99bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_qh99bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:auto-flash" {...props}></Icon>
