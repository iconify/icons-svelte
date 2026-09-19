<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u72cutb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u72cutb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:lollipop" {...props}></Icon>
