<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5aunccht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="x5aunccht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:laugh-wink" {...props}></Icon>
