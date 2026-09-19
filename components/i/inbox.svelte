<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/jgaqzcb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="1.75 13.25 14.25 13.25 14.25 8.25 11.75 2.75 4.25 2.75 1.75 8.25"/><path class="jgaqzcb5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:inbox" {...props}></Icon>
