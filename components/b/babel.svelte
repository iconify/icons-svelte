<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8yywaboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1349,"height":519};
const content = `<path class="i8yywaboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:babel" {...props}></Icon>
