<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsi2vccmn.css';
import '../../css/f/fjxpc8spu.css';
import '../../css/r/re2dj7mko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bsi2vccmn"/><path class="fjxpc8spu"/><path class="re2dj7mko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:passkey-20-bold" {...props}></Icon>
