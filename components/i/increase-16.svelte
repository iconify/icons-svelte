<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8l00fqcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v8l00fqcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:increase-16" {...props}></Icon>
