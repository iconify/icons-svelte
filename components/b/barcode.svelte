<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1a51kbri.css';
import '../../css/x/xb8nkibtq.css';
import '../../css/a/ajx3eoq3x.css';
import '../../css/q/qeicwlb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1a51kbri wm-shadow"/><path class="wm-k xb8nkibtq"/><path class="ajx3eoq3x wm-k"/><path class="qeicwlb3y wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:barcode" {...props}></Icon>
