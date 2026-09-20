<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omcmqybsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="omcmqybsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-prescription" {...props}></Icon>
