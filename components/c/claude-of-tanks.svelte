<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omuyjcckl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":9956,"height":700,"left":55,"top":142};
const content = `<path class="omuyjcckl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:claude-of-tanks" {...props}></Icon>
