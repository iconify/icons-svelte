<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-xtz-b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="s-xtz-b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-symlink-directory" {...props}></Icon>
