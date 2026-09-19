<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbsj5lbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bbsj5lbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:jnt" {...props}></Icon>
