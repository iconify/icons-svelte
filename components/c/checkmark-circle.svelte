<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxzl7z52l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxzl7z52l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:checkmark-circle" {...props}></Icon>
