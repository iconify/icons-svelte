<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/banyp_byo.css';
import '../../css/k/kk04ncb8k.css';
import '../../css/d/dssrzebmt.css';
import '../../css/p/pt94-ibub.css';
import '../../css/o/obvm_z7qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<circle class="banyp_byo"/><path clip-rule="evenodd" class="kk04ncb8k"/><path clip-rule="evenodd" class="dssrzebmt"/><path class="pt94-ibub"/><path class="obvm_z7qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:magic" {...props}></Icon>
