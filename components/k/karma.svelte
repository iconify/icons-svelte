<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om4mwxbqv.css';
import '../../css/i/i4ou1xbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="om4mwxbqv"/><path class="i4ou1xbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:karma" {...props}></Icon>
