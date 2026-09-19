<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ral5x2b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="ral5x2b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:meh-blank" {...props}></Icon>
