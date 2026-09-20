<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws20coc9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ws20coc9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:double-arrow-right-filled" {...props}></Icon>
