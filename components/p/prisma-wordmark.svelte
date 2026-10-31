<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3v_b68vp.css';
import '../../css/b/bcdhxdblm.css';
import '../../css/l/lwi4j495p.css';
import '../../css/d/dko403b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k3v_b68vp"/><path class="bcdhxdblm"/><path class="lwi4j495p"/><path class="dko403b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:prisma-wordmark" {...props}></Icon>
