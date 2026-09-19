<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2z099a8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x2z099a8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:address-card" {...props}></Icon>
