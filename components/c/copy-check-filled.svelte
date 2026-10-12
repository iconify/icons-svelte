<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upt8xbe-t.css';
import '../../css/u/uwmcnls3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="upt8xbe-t"/><path class="uwmcnls3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:copy-check-filled" {...props}></Icon>
