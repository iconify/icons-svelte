<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gry1pgb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="gry1pgb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:poi-favorite" {...props}></Icon>
