<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oucwh3zmg.css';
import '../../css/j/jnyh7fqkv.css';
import '../../css/s/s1cu90uay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle transform="rotate(-1.057 159.995 423.97) scale(.99997)" class="oucwh3zmg"/><circle transform="matrix(.02382 -.9997 .9997 .02382 -48.51 798.282)" class="jnyh7fqkv"/><path class="s1cu90uay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cart" {...props}></Icon>
