<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anw-b9pqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="anw-b9pqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-top-right-and-minus" {...props}></Icon>
