<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwdr9chfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wwdr9chfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-contract" {...props}></Icon>
