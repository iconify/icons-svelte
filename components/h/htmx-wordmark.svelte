<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlw9lr9hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xlw9lr9hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:htmx-wordmark" {...props}></Icon>
