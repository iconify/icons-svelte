<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eahdk6b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eahdk6b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openzfs" {...props}></Icon>
