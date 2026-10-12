<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ineotobot.css';
import '../../css/j/j9mguybwz.css';
import '../../css/g/gjba8cbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ineotobot"/><path clip-rule="evenodd" class="j9mguybwz"/><path class="gjba8cbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-search-filled" {...props}></Icon>
