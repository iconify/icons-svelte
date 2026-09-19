<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugvlctb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ugvlctb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-webmethods-b2b-integration" {...props}></Icon>
