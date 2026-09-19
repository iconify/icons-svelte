<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfj0fgbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfj0fgbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:code-slash-outline" {...props}></Icon>
