<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvt7f_k7b.css';
import '../../css/t/t0khrkc2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvt7f_k7b"/><path class="t0khrkc2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-arrow-left-filled" {...props}></Icon>
