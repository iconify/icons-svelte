<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcstgtvsf.css';
import '../../css/f/fbb_pv2ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcstgtvsf"/><path class="fbb_pv2ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cxo" {...props}></Icon>
