<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd1la8bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="kd1la8bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:elsevier" {...props}></Icon>
