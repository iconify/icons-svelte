<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf3d79iqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yf3d79iqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cooked-rice" {...props}></Icon>
