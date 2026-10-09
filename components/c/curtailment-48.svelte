<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-py7pbjn.css';
import '../../css/d/d59gayyww.css';
import '../../css/m/m0ym9zbob.css';
import '../../css/c/c_xh25dlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u-py7pbjn"/><path class="d59gayyww"/><path class="m0ym9zbob"/><path class="c_xh25dlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:curtailment-48" {...props}></Icon>
