<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec4h7ebhn.css';
import '../../css/x/xz2t00wzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ec4h7ebhn"/><path class="xz2t00wzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-jobs-20" {...props}></Icon>
