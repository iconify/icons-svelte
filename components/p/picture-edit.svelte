<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np37u6blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":16};
const content = `<path class="np37u6blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:picture-edit" {...props}></Icon>
