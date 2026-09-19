<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le4acc5tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="le4acc5tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:motorola" {...props}></Icon>
