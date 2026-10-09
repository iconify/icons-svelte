<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmratjbob.css';
import '../../css/a/av226wb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rmratjbob"/><path class="av226wb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desert-20" {...props}></Icon>
