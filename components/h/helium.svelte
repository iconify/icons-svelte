<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo7cxv9ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo7cxv9ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:helium" {...props}></Icon>
