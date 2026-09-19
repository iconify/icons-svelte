<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2g91qadi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="x2g91qadi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:progress-4" {...props}></Icon>
