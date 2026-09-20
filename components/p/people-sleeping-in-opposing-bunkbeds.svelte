<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dup2ybc4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dup2ybc4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-sleeping-in-opposing-bunkbeds" {...props}></Icon>
