<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gszu5hdad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gszu5hdad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bricks" {...props}></Icon>
