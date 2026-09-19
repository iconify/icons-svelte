<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n6onabcla.css';
import '../../css/m/md286fbip.css';
import '../../css/t/t_vxkebwj.css';
import '../../css/n/nnhhj0b3v.css';
import '../../css/z/zt91rkbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="n6onabcla"/><g class="md286fbip"><path class="t_vxkebwj"/><path class="nnhhj0b3v"/><path class="zt91rkbak"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:aywa" {...props}></Icon>
