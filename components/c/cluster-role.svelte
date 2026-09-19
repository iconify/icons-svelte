<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtmxd4b4h.css';
import '../../css/r/rn2kcz5al.css';
import '../../css/l/lg6jjqbgi.css';
import '../../css/t/t74-6o1oe.css';
import '../../css/y/y4_fhtb_d.css';
import '../../css/k/kpxfszbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtmxd4b4h"/><circle class="rn2kcz5al"/><circle class="lg6jjqbgi"/><circle class="t74-6o1oe"/><circle class="y4_fhtb_d"/><path class="kpxfszbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:cluster-role" {...props}></Icon>
