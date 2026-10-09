<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm8uiwbzj.css';
import '../../css/w/wcp6j0b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qm8uiwbzj"/><path class="wcp6j0b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-chademo-20-bold" {...props}></Icon>
