<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7j8ofo6z.css';
import '../../css/l/lf3nfothj.css';
import '../../css/z/zp_lnpb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r7j8ofo6z"/><path class="lf3nfothj"/><path class="zp_lnpb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:money" {...props}></Icon>
