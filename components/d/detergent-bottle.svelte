<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-wk0oblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f-wk0oblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:detergent-bottle" {...props}></Icon>
