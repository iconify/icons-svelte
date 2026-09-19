<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfc3gybyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":283,"height":512};
const content = `<path class="qfc3gybyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ballerina" {...props}></Icon>
