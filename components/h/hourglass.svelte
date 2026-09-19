<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv0q8b-8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vv0q8b-8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:hourglass" {...props}></Icon>
