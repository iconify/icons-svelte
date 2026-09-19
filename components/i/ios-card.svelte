<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li_aurb-v.css';
import '../../css/q/qv-j8ebyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="li_aurb-v"/><path class="qv-j8ebyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-card" {...props}></Icon>
