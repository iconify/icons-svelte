<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqpcc4bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bqpcc4bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-16-solid" {...props}></Icon>
