<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dswamh2es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dswamh2es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-chevron-right" {...props}></Icon>
