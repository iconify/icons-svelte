<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttpbghffn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ttpbghffn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:circle-outline" {...props}></Icon>
