<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_uoe7b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w_uoe7b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cloud" {...props}></Icon>
