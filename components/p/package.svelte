<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/iusjtvbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="1.75 5.75 1.75 14.25 1.75 14.25 14.25 14.25 14.25 5.75 10.75 1.75 5.25 1.75"/><path class="iusjtvbzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:package" {...props}></Icon>
