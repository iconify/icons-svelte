<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbc1rkbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wbc1rkbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:aries" {...props}></Icon>
