<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otv6zerrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="otv6zerrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:record-stroke-16" {...props}></Icon>
