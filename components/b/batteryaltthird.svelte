<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdgqg2iiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="wdgqg2iiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:batteryaltthird" {...props}></Icon>
