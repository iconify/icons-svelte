<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s79j0rq-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s79j0rq-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:l" {...props}></Icon>
