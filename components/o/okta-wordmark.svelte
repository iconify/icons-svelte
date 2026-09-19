<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7e5t-z9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u7e5t-z9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:okta-wordmark" {...props}></Icon>
