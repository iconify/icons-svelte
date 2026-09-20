<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlymt9bdv.css';
import '../../css/t/t6brsoc_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hlymt9bdv"/><path class="t6brsoc_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:crossing-markings-ladder-paired" {...props}></Icon>
