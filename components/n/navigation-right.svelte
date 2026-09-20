<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp3_9h6db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lp3_9h6db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:navigation-right" {...props}></Icon>
