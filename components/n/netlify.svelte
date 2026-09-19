<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a01e7gm4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a01e7gm4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:netlify" {...props}></Icon>
