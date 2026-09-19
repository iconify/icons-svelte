<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpjqfiz0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bpjqfiz0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:log-in" {...props}></Icon>
