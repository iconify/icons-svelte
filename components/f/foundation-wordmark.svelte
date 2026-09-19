<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjzy66b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qjzy66b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:foundation-wordmark" {...props}></Icon>
