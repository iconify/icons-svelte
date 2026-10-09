<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwup6hyfp.css';
import '../../css/k/k6p64wbai.css';
import '../../css/h/hik87rbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kwup6hyfp"/><path class="k6p64wbai"/><path class="hik87rbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-alert-20" {...props}></Icon>
