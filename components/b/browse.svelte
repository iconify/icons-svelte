<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvs5jlb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":16};
const content = `<path class="vvs5jlb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:browse" {...props}></Icon>
