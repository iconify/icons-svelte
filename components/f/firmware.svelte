<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt1rgy1os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tt1rgy1os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:firmware" {...props}></Icon>
