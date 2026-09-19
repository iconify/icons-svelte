<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgi0i4ykh.css';
import '../../css/e/e1am0fiug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tgi0i4ykh"/><path class="e1am0fiug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-albums" {...props}></Icon>
