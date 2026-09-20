<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8vm9wbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n8vm9wbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ahrefs" {...props}></Icon>
