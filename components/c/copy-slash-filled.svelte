<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt3rw1bev.css';
import '../../css/u/uwmcnls3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xt3rw1bev"/><path class="uwmcnls3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:copy-slash-filled" {...props}></Icon>
