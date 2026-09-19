<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddq1u26pl.css';
import '../../css/l/l71mrm8fk.css';
import '../../css/h/hh_hn2b_u.css';
import '../../css/m/m4ajnwsrg.css';
import '../../css/i/iwke2cbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ddq1u26pl"/><circle class="l71mrm8fk"/><path class="hh_hn2b_u"/><circle class="m4ajnwsrg"/><path class="iwke2cbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-satellite-config" {...props}></Icon>
