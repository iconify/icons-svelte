<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr827abeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gr827abeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:image-alt-outline" {...props}></Icon>
