<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwq-xk6uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bwq-xk6uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-folder-small-filled" {...props}></Icon>
