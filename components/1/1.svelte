<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t79s19b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":1024};
const content = `<path class="t79s19b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:1" {...props}></Icon>
