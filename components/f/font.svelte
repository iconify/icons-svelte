<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow9tyrz_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":925,"height":1000};
const content = `<path class="ow9tyrz_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:font" {...props}></Icon>
