<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_mbj975l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_mbj975l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:noon" {...props}></Icon>
