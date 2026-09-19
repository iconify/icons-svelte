<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewl7-nb0r.css';
import '../../css/q/qou13c05m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ewl7-nb0r"/><path class="qou13c05m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:battery-2-filled" {...props}></Icon>
