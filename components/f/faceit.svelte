<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfn29bgpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfn29bgpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:faceit" {...props}></Icon>
