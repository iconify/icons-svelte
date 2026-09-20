<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr-s73b2l.css';
import '../../css/z/z82ok8llb.css';
import '../../css/c/c_6h8cous.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr-s73b2l"/><path class="z82ok8llb"/><path class="c_6h8cous"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bdt" {...props}></Icon>
