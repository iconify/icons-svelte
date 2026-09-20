<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6tshe-ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d6tshe-ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:medal-ribbon-with-star" {...props}></Icon>
