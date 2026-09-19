<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad3ep5b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ad3ep5b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:indent-left" {...props}></Icon>
