<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1lkjqb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d1lkjqb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:navigation" {...props}></Icon>
