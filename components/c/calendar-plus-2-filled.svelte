<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqe4zc3ni.css';
import '../../css/g/gjba8cbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqe4zc3ni"/><path class="gjba8cbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-plus-2-filled" {...props}></Icon>
