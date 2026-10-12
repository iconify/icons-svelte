<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0sb-0bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0sb-0bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mic-signal-filled" {...props}></Icon>
