<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpmo8pb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="dpmo8pb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ivy-framework" {...props}></Icon>
