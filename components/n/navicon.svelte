<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glgc2s32b.css';
import '../../css/t/t6zyl3h8b.css';
import '../../css/n/naljiqsza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="glgc2s32b"/><path class="t6zyl3h8b"/><path class="naljiqsza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:navicon" {...props}></Icon>
