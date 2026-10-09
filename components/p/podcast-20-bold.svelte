<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxmq_uzjj.css';
import '../../css/o/o8au-u-tj.css';
import '../../css/z/zi_t7ybkv.css';
import '../../css/p/pv-y02gkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kxmq_uzjj"/><path class="o8au-u-tj"/><path class="zi_t7ybkv"/><path class="pv-y02gkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:podcast-20-bold" {...props}></Icon>
