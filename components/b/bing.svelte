<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcgl4ebri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tcgl4ebri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bing" {...props}></Icon>
