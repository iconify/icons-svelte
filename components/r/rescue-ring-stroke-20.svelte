<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkklicbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bkklicbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:rescue-ring-stroke-20" {...props}></Icon>
