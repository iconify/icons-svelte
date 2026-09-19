<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjdzctb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qjdzctb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:apify-wordmark" {...props}></Icon>
