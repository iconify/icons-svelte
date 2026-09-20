<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdkeg8bno.css';
import '../../css/r/ro17tb5-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="bdkeg8bno"/><path class="ro17tb5-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anyappstart" {...props}></Icon>
