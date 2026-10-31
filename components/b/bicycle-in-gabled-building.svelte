<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo0m-bcql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eo0m-bcql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-in-gabled-building" {...props}></Icon>
