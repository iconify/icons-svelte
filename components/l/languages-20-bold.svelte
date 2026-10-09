<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4d3-1mti.css';
import '../../css/a/ay8umis1r.css';
import '../../css/o/o49-qrbbn.css';
import '../../css/i/iu_u5m5mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k4d3-1mti"/><path class="ay8umis1r"/><path class="o49-qrbbn"/><path class="iu_u5m5mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:languages-20-bold" {...props}></Icon>
