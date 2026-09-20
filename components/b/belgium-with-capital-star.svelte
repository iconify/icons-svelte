<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r498tf0fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r498tf0fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:belgium-with-capital-star" {...props}></Icon>
