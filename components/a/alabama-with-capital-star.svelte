<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b244-_biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b244-_biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:alabama-with-capital-star" {...props}></Icon>
