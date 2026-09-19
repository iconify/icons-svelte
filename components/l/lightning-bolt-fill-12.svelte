<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nic15ybst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nic15ybst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lightning-bolt-fill-12" {...props}></Icon>
