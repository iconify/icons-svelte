<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwt559b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iwt559b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:garden-centre-14" {...props}></Icon>
