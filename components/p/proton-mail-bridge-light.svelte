<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aph_dqbwx.css';
import '../../css/r/rulnoebmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aph_dqbwx"/><path class="rulnoebmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-mail-bridge-light" {...props}></Icon>
