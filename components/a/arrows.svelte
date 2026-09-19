<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-937wkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="bp-937wkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrows" {...props}></Icon>
