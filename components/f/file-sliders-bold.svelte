<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpfnlu-qi.css';
import '../../css/k/kgek_1bkv.css';
import '../../css/p/pctlhgoqh.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpfnlu-qi"/><path class="kgek_1bkv"/><path clip-rule="evenodd" class="pctlhgoqh"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-sliders-bold" {...props}></Icon>
