<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txfkbpb1g.css';
import '../../css/y/y7nz84h9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="txfkbpb1g"/><path class="y7nz84h9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-plane-20-bold" {...props}></Icon>
