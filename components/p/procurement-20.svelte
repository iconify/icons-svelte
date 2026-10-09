<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvm_9zb2m.css';
import '../../css/w/wx5f8bcnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jvm_9zb2m"/><path class="wx5f8bcnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:procurement-20" {...props}></Icon>
