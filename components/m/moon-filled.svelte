<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwbewhi_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jwbewhi_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:moon-filled" {...props}></Icon>
