<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl4umccal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xl4umccal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:right-to-bracket" {...props}></Icon>
