<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa67-jbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fa67-jbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:3-plus" {...props}></Icon>
