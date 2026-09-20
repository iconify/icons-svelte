<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ail75ac-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ail75ac-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:domain" {...props}></Icon>
