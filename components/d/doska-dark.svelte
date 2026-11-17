<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qebs_l2bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qebs_l2bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:doska-dark" {...props}></Icon>
