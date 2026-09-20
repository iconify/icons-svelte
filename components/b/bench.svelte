<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0eluub0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c0eluub0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bench" {...props}></Icon>
