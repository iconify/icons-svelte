<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unaljlb8v.css';
import '../../css/s/szt_lz6ub.css';
import '../../css/l/l71mrm8fk.css';
import '../../css/h/hh_hn2b_u.css';
import '../../css/m/m4ajnwsrg.css';
import '../../css/f/fjvik3r7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="unaljlb8v"/><path class="szt_lz6ub"/><circle class="l71mrm8fk"/><path class="hh_hn2b_u"/><circle class="m4ajnwsrg"/><path class="fjvik3r7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-satellite-link" {...props}></Icon>
