<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwh-h-rhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jwh-h-rhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-right-circle-outline" {...props}></Icon>
