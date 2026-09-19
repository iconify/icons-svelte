<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o70vwv53g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o70vwv53g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-round-back" {...props}></Icon>
