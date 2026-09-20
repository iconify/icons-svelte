<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6ngwtb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d6ngwtb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:prostate" {...props}></Icon>
