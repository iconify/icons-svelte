<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns7diqbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ns7diqbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:parent-node" {...props}></Icon>
