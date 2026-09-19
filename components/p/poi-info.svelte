<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7wez5bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="x7wez5bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:poi-info" {...props}></Icon>
