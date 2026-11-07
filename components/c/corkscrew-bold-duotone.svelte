<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma2gzy3et.css';
import '../../css/t/tpblc1bjs.css';
import '../../css/q/qsvxid4dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma2gzy3et"/><path class="tpblc1bjs"/><path class="qsvxid4dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:corkscrew-bold-duotone" {...props}></Icon>
