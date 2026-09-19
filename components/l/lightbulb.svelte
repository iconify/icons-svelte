<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maqn9jbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="maqn9jbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:lightbulb" {...props}></Icon>
