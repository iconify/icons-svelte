<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwa4pl89p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uwa4pl89p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:okta" {...props}></Icon>
