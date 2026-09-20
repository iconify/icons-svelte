<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur_1lrlwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ur_1lrlwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-v-over-water" {...props}></Icon>
