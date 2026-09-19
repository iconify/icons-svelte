<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1_exgbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e1_exgbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:add-outline" {...props}></Icon>
