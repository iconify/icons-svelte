<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkn7fcxyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wkn7fcxyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:imac-solid" {...props}></Icon>
