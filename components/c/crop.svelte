<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn6qy6jmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zn6qy6jmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:crop" {...props}></Icon>
