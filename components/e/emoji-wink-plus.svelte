<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5eph-bdq.css';
import '../../css/q/qr4wsabqv.css';
import '../../css/g/ga3lzib3e.css';
import '../../css/n/njhb20v1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5eph-bdq"/><path class="qr4wsabqv"/><path class="ga3lzib3e"/><path clip-rule="evenodd" class="njhb20v1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:emoji-wink-plus" {...props}></Icon>
