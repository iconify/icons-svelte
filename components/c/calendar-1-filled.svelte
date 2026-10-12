<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckmtaeugr.css';
import '../../css/g/gjba8cbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckmtaeugr"/><path class="gjba8cbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-1-filled" {...props}></Icon>
