<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv46repqa.css';
import '../../css/r/ra5u6pzcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kv46repqa"/><path class="ra5u6pzcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rocket-20-bold" {...props}></Icon>
