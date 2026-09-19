<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcraqe0wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qcraqe0wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cloud-moon" {...props}></Icon>
