<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfnl83bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfnl83bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grin-tongue" {...props}></Icon>
