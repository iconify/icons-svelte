<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnvjrjbfl.css';
import '../../css/o/o7x01qbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nnvjrjbfl"/><path class="o7x01qbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:at" {...props}></Icon>
