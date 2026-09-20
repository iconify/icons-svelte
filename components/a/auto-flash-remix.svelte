<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7v_mpb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d7v_mpb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:auto-flash-remix" {...props}></Icon>
