<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yihqpin0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yihqpin0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:recycle-bin-remix" {...props}></Icon>
