<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1_o48b8v.css';
import '../../css/w/w2o_n1p2a.css';
import '../../css/i/i-41ktb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t1_o48b8v"/><path class="w2o_n1p2a"/><path clip-rule="evenodd" class="i-41ktb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:paste-16" {...props}></Icon>
