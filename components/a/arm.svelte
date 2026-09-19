<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6c71_qzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6c71_qzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:arm" {...props}></Icon>
