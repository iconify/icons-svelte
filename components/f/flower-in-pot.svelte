<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrtz2jb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jrtz2jb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:flower-in-pot" {...props}></Icon>
