<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjwzmm--m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pjwzmm--m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:potion" {...props}></Icon>
