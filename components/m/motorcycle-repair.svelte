<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2yxyub9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a2yxyub9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:motorcycle-repair" {...props}></Icon>
