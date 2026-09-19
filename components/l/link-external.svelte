<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v0rzmlrzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polyline points="8.25 2.75 2.75 2.75 2.75 13.25 13.25 13.25 13.25 7.75"/><path class="v0rzmlrzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:link-external" {...props}></Icon>
