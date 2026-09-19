<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9n72kbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1088,"height":1664};
const content = `<g transform="translate(1088 0) scale(-1 1)"><path class="n9n72kbnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chevron-right" {...props}></Icon>
