<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2mk6acez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="b2mk6acez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:phone-flat" {...props}></Icon>
