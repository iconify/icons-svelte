<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq903rb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sq903rb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:parking" {...props}></Icon>
