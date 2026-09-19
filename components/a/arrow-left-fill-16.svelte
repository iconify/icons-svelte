<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue1naxbat.css';
import '../../css/w/wwd7qgbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ue1naxbat"/><path class="wwd7qgbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-left-fill-16" {...props}></Icon>
