<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nllo96y1n.css';
import '../../css/r/ro4pfvbsr.css';
import '../../css/k/kb3bwobho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nllo96y1n"/><path class="ro4pfvbsr"/><path class="kb3bwobho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:kanban-bold" {...props}></Icon>
