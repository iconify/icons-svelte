<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwstf9b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wwstf9b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:8-circle-fill" {...props}></Icon>
