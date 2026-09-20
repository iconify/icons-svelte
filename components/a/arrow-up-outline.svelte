<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn3zk-1ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yn3zk-1ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:arrow-up-outline" {...props}></Icon>
