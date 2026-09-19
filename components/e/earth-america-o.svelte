<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8t325kav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="b8t325kav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-america-o" {...props}></Icon>
