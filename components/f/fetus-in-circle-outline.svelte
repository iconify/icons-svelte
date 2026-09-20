<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9ofombbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d9ofombbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fetus-in-circle-outline" {...props}></Icon>
