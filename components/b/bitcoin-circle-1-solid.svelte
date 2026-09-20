<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq_tbluok.css';
import '../../css/q/qcret227i.css';
import '../../css/z/zsyn02zgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uq_tbluok"/><path clip-rule="evenodd" class="qcret227i"/><path clip-rule="evenodd" class="zsyn02zgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bitcoin-circle-1-solid" {...props}></Icon>
