<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lquupobmq.css';
import '../../css/p/pln5qlbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lquupobmq"/><path class="pln5qlbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:ellipses-horizontal-circle" {...props}></Icon>
