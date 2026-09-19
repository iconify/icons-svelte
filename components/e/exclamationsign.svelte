<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee-cf28xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ee-cf28xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:exclamationsign" {...props}></Icon>
