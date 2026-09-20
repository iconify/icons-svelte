<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vism6qblg.css';
import '../../css/n/nnx_4qb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vism6qblg"/><path class="nnx_4qb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-refresh-light" {...props}></Icon>
