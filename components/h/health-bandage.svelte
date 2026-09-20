<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byt1vbcft.css';
import '../../css/u/ue2etpb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="byt1vbcft"/><path class="ue2etpb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-bandage" {...props}></Icon>
