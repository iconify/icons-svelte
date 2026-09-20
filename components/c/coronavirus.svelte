<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe3qr6bzc.css';
import '../../css/b/bkyqy-baq.css';
import '../../css/j/jg2dkzt5u.css';
import '../../css/t/t4ulnobzr.css';
import '../../css/r/rirsv2xyn.css';
import '../../css/d/dmrojcb9v.css';
import '../../css/f/fxqvrobnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="oe3qr6bzc"/><circle class="bkyqy-baq"/><circle class="jg2dkzt5u"/><circle class="t4ulnobzr"/><path class="rirsv2xyn"/><path class="dmrojcb9v"/><path class="fxqvrobnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:coronavirus" {...props}></Icon>
