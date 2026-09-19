<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow40lcb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ow40lcb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:dtube" {...props}></Icon>
