<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojjz05b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":800};
const content = `<path class="ojjz05b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:dialog" {...props}></Icon>
