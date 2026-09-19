<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3qf5l6ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j3qf5l6ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-down-circle" {...props}></Icon>
