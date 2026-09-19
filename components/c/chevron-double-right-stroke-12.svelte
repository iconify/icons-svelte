<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya3uagblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ya3uagblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-right-stroke-12" {...props}></Icon>
