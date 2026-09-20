<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajmjvabeq.css';
import '../../css/a/acfb3gbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":208,"height":92};
const content = `<path class="ajmjvabeq"/><path class="acfb3gbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:amul-info" {...props}></Icon>
