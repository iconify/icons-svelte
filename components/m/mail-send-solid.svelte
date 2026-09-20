<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf-dlbakk.css';
import '../../css/l/l_7c63odl.css';
import '../../css/s/srjf_ccfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nf-dlbakk"/><path class="l_7c63odl"/><path clip-rule="evenodd" class="srjf_ccfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-send-solid" {...props}></Icon>
