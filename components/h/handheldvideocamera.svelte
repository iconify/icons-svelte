<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es97rtbpl.css';
import '../../css/m/mhn45ibqb.css';
import '../../css/m/m2897mb0i.css';
import '../../css/z/zk30aempb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="es97rtbpl"/><path class="mhn45ibqb"/><circle class="m2897mb0i"/><path class="zk30aempb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:handheldvideocamera" {...props}></Icon>
