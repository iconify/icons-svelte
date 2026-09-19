<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsc_azbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fsc_azbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:align-vertical-top" {...props}></Icon>
