<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s66i86wmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s66i86wmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:arrow-down" {...props}></Icon>
