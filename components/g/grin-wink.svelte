<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr94xlp5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="tr94xlp5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin-wink" {...props}></Icon>
