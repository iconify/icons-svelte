<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7paa7bvz.css';
import '../../css/e/eq1itn6jt.css';
import '../../css/y/yfnsrpb6h.css';
import '../../css/t/tlsr_qb5c.css';
import '../../css/m/m-w8fnz7e.css';
import '../../css/s/sd6il-b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u7paa7bvz"/><path class="eq1itn6jt"/><path class="yfnsrpb6h"/><path class="tlsr_qb5c"/><path class="m-w8fnz7e"/><path class="sd6il-b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:pencil" {...props}></Icon>
