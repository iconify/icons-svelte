<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/temjivdtd.css';
import '../../css/e/e3yi-0i_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="temjivdtd"/><path class="e3yi-0i_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-personadd" {...props}></Icon>
