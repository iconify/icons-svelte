<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7sr6ubzr.css';
import '../../css/d/da52qgv7e.css';
import '../../css/k/khjjc1bwg.css';
import '../../css/j/jv73pqbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><path class="da52qgv7e"/><path class="khjjc1bwg"/><circle class="jv73pqbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-vision-api" {...props}></Icon>
