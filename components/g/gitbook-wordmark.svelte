<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yme_38p6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yme_38p6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gitbook-wordmark" {...props}></Icon>
