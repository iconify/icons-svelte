<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgy1l_tlx.css';
import '../../css/n/nx7dqhb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hgy1l_tlx"/><path class="nx7dqhb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-right-20-bold" {...props}></Icon>
