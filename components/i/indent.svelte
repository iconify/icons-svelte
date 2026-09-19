<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vseh-l-0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="vseh-l-0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:indent" {...props}></Icon>
