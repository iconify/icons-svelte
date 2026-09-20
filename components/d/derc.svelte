<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmj18yb6f.css';
import '../../css/t/tfqe-pf5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmj18yb6f"/><path class="tfqe-pf5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:derc" {...props}></Icon>
