<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt_4_ts2l.css';
import '../../css/o/oak52ubup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mt_4_ts2l"/><path class="oak52ubup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:email-mailbox-close" {...props}></Icon>
