<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hui9kbcjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hui9kbcjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-all-outline" {...props}></Icon>
