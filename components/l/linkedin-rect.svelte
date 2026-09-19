<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x848pdb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="x848pdb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:linkedin-rect" {...props}></Icon>
