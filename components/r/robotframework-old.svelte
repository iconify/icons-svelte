<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofs7f2bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ofs7f2bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:robotframework-old" {...props}></Icon>
