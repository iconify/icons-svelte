<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7l2_07fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7l2_07fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:book-open" {...props}></Icon>
