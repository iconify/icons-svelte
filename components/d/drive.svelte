<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx9bgwqht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xx9bgwqht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:drive" {...props}></Icon>
