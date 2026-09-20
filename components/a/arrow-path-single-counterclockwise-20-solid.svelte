<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr6pcpboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tr6pcpboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-single-counterclockwise-20-solid" {...props}></Icon>
