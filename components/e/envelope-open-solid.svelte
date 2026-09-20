<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifuc-ccmq.css';
import '../../css/q/qhzz97u4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ifuc-ccmq"/><path class="qhzz97u4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:envelope-open-solid" {...props}></Icon>
