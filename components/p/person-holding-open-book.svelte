<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t09269bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t09269bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-holding-open-book" {...props}></Icon>
