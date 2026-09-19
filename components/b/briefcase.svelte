<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4vak2i9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="r4vak2i9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:briefcase" {...props}></Icon>
