<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkq7-hbwz.css';
import '../../css/r/rmslx6b5x.css';
import '../../css/b/bzun-yi8p.css';
import '../../css/i/i1r7m_bpd.css';
import '../../css/g/g0oj0e-rq.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jkq7-hbwz"/><path class="rmslx6b5x"/><path class="bzun-yi8p"/><circle class="i1r7m_bpd"/><path class="g0oj0e-rq"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-mexico" {...props}></Icon>
