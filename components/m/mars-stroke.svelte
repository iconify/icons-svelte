<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-grg3b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="a-grg3b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mars-stroke" {...props}></Icon>
