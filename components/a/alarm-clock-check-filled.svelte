<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usigsbd8n.css';
import '../../css/d/du-r1xbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usigsbd8n"/><path class="du-r1xbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:alarm-clock-check-filled" {...props}></Icon>
