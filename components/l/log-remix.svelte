<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjj53xb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zjj53xb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:log-remix" {...props}></Icon>
