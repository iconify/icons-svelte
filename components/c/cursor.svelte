<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="1.75 1.75 6.25 14.25 8.75 8.75 14.25 6.25"/><line x1="9.25" x2="13.25" y1="9.25" y2="13.25"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:cursor" {...props}></Icon>
