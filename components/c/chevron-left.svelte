<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9n72kbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1088,"height":1664};
const content = `<path class="n9n72kbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chevron-left" {...props}></Icon>
