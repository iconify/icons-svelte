<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgkjyd2eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pgkjyd2eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-import-filled" {...props}></Icon>
