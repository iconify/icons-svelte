<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp27lvbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jp27lvbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mercurial" {...props}></Icon>
