<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twfn9u9ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="twfn9u9ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bat-20" {...props}></Icon>
