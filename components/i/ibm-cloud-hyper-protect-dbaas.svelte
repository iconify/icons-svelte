<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjgbk469t.css';
import '../../css/p/pcn7t_b3w.css';
import '../../css/c/cdkh7bjct.css';
import '../../css/a/a6w2ebnxk.css';
import '../../css/s/skgtwgb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sjgbk469t"/><circle class="pcn7t_b3w"/><circle class="cdkh7bjct"/><circle class="a6w2ebnxk"/><path class="skgtwgb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-hyper-protect-dbaas" {...props}></Icon>
