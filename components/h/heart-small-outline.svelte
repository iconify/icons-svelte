<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6jc6kbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y6jc6kbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:heart-small-outline" {...props}></Icon>
