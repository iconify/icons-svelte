<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2nrf10bf.css';
import '../../css/i/i-sqrpb3f.css';
import '../../css/r/rzypoebor.css';
import '../../css/z/zmdi14bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path class="i-sqrpb3f"/><path class="rzypoebor"/><path class="zmdi14bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-kanban-bold-duotone" {...props}></Icon>
