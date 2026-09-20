<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peq-q4buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="peq-q4buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:drink-food-cookie" {...props}></Icon>
