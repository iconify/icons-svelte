<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8xwu9g6i.css';
import '../../css/s/stdxmbcpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect transform="rotate(-90 256 256)" class="s8xwu9g6i"/><path class="stdxmbcpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:phone-landscape-outline" {...props}></Icon>
