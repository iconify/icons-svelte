<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbf9zkbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rbf9zkbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:file-box-and-tag" {...props}></Icon>
