<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za7cltxdg.css';
import '../../css/v/v_my3mlnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="za7cltxdg"/><path class="v_my3mlnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:banknoteeuro" {...props}></Icon>
