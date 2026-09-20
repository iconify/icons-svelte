<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbsaxbc2m.css';
import '../../css/k/k7cxakrzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbsaxbc2m"/><path class="k7cxakrzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:print" {...props}></Icon>
