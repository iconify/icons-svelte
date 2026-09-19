<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5dsbbc0o.css';
import '../../css/l/l71mrm8fk.css';
import '../../css/h/hh_hn2b_u.css';
import '../../css/m/m4ajnwsrg.css';
import '../../css/i/iwke2cbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u5dsbbc0o"/><circle class="l71mrm8fk"/><path class="hh_hn2b_u"/><circle class="m4ajnwsrg"/><path class="iwke2cbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-satellite-services" {...props}></Icon>
