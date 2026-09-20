<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gja2j7b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gja2j7b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-with-shekel" {...props}></Icon>
