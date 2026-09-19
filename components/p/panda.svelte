<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rimfd1bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1025};
const content = `<path class="rimfd1bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:panda" {...props}></Icon>
