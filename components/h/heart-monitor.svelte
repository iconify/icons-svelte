<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo2ouibij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yo2ouibij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:heart-monitor" {...props}></Icon>
