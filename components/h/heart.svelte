<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdbzq-bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fdbzq-bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:heart" {...props}></Icon>
