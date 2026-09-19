<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu1g5acvh.css';
import '../../css/k/kq1i8jlgx.css';
import '../../css/q/qbfao4-vr.css';
import '../../css/r/rbqpjolra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bu1g5acvh"/><path class="kq1i8jlgx"/><path class="qbfao4-vr"/><path class="rbqpjolra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:newspaper-outline" {...props}></Icon>
