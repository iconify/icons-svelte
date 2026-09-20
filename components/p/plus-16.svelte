<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx00fkbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wx00fkbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:plus-16" {...props}></Icon>
