<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6be-kb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a6be-kb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:labview" {...props}></Icon>
