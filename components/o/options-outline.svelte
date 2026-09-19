<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5vc2lbnc.css';
import '../../css/o/o70nwy-rj.css';
import '../../css/h/hr1b_yvco.css';
import '../../css/i/its46bcpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l5vc2lbnc"/><circle class="o70nwy-rj"/><circle class="hr1b_yvco"/><circle class="its46bcpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:options-outline" {...props}></Icon>
