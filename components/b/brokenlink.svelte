<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4z7z5blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="h4z7z5blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brokenlink" {...props}></Icon>
