<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s29wwbcwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s29wwbcwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-left-from-right-bracket" {...props}></Icon>
