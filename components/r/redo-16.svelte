<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk8wbdc9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hk8wbdc9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:redo-16" {...props}></Icon>
