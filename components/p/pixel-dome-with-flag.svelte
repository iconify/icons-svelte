<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_5_6fbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p_5_6fbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-dome-with-flag" {...props}></Icon>
