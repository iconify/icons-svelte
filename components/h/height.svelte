<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq6c9gc0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="aq6c9gc0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:height" {...props}></Icon>
