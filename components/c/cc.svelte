<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/ki0xnbcvt.css';
import '../../css/m/md286fbip.css';
import '../../css/k/kn8bd-bng.css';
import '../../css/h/hx2tq71se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="ki0xnbcvt"/><g class="md286fbip"><path class="kn8bd-bng"/><path class="hx2tq71se"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:cc" {...props}></Icon>
