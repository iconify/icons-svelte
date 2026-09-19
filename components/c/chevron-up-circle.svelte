<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqbkv8u2i.css';
import '../../css/l/lml2oc9mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="lml2oc9mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:chevron-up-circle" {...props}></Icon>
