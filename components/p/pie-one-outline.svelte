<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js03r1bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="js03r1bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:pie-one-outline" {...props}></Icon>
