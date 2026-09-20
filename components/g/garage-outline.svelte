<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxtcn-bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nxtcn-bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:garage-outline" {...props}></Icon>
