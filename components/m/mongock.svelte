<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyt9-sb9b.css';
import '../../css/p/penv9lb5j.css';
import '../../css/m/m1hgx9ntx.css';
import '../../css/u/upa9vcbvf.css';
import '../../css/x/xmk0yknes.css';
import '../../css/s/skk1shfyp.css';
import '../../css/c/c5s_mibno.css';
import '../../css/b/b6aszybqn.css';
import '../../css/p/pf3n8qo0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lyt9-sb9b"/><path class="penv9lb5j"/><path class="m1hgx9ntx"/><path class="upa9vcbvf"/><path class="xmk0yknes"/><path class="skk1shfyp"/><path class="c5s_mibno"/><path class="b6aszybqn"/><path class="pf3n8qo0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mongock" {...props}></Icon>
