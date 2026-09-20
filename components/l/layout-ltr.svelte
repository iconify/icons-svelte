<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf7wu2l-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wf7wu2l-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:layout-ltr" {...props}></Icon>
