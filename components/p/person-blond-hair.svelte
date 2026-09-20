<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amn_b-_3e.css';
import '../../css/n/ncz70n-in.css';
import '../../css/n/nd9p_7cqd.css';
import '../../css/k/k39h0tblb.css';
import '../../css/y/y6fqwjbfy.css';
import '../../css/m/m-l90ob2o.css';
import '../../css/l/l_8clz36z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="amn_b-_3e"/><path class="ncz70n-in"/><path class="nd9p_7cqd"/><path class="k39h0tblb"/><path class="y6fqwjbfy"/><path class="m-l90ob2o"/><path class="l_8clz36z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:person-blond-hair" {...props}></Icon>
