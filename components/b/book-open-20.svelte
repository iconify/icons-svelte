<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlk1-zbma.css';
import '../../css/l/l016wdj-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rlk1-zbma"/><path class="l016wdj-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:book-open-20" {...props}></Icon>
