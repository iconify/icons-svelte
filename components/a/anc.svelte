<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9ou3fpyy.css';
import '../../css/c/cq_4pmbzu.css';
import '../../css/u/umr51jx_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9ou3fpyy"/><path class="cq_4pmbzu"/><path clip-rule="evenodd" class="umr51jx_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:anc" {...props}></Icon>
