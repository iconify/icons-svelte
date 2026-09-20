<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4p__bc9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f4p__bc9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:default" {...props}></Icon>
