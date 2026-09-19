<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv5cqiwwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="iv5cqiwwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:directions" {...props}></Icon>
