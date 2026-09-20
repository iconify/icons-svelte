<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liaioib8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="liaioib8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:file-x-outline" {...props}></Icon>
