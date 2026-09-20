<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmi6sy-ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gmi6sy-ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:python-outline" {...props}></Icon>
