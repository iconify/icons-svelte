<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax-isfbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ax-isfbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:page-number-outline" {...props}></Icon>
