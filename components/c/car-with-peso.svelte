<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr3gh3_tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gr3gh3_tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-peso" {...props}></Icon>
