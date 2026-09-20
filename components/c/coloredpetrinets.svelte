<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co4u79bom.css';
import '../../css/t/t_qykii2y.css';
import '../../css/b/b6znd0b_r.css';
import '../../css/d/dgcljpugd.css';
import '../../css/g/gt-o6rbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="co4u79bom"/><rect class="t_qykii2y"/><circle class="b6znd0b_r"/><circle class="dgcljpugd"/><rect class="gt-o6rbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:coloredpetrinets" {...props}></Icon>
