<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="1.75 11.25 1.75 14.25 4.75 14.25 14.25 4.75 11.25 1.75"/><line x1="8.75" x2="11.25" y1="4.75" y2="7.25"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:pencil" {...props}></Icon>
