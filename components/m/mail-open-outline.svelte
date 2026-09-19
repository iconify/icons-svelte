<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynacwacmn.css';
import '../../css/k/kmd5rqb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ynacwacmn"/><path class="kmd5rqb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:mail-open-outline" {...props}></Icon>
