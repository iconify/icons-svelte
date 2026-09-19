<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6tlx3boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h6tlx3boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:number-fill-16" {...props}></Icon>
