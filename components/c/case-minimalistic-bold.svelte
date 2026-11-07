<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnj8zni5c.css';
import '../../css/q/qo_wu9b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnj8zni5c"/><path clip-rule="evenodd" class="qo_wu9b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-minimalistic-bold" {...props}></Icon>
