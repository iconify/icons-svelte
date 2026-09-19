<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duyp1yy5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="duyp1yy5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cordova-wordmark" {...props}></Icon>
