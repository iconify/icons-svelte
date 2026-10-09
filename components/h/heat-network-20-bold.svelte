<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qho2-b78i.css';
import '../../css/c/cu2uiexyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qho2-b78i"/><path class="cu2uiexyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-network-20-bold" {...props}></Icon>
