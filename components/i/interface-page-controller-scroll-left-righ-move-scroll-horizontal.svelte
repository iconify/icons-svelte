<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iil-_0epu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iil-_0epu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-page-controller-scroll-left-righ-move-scroll-horizontal" {...props}></Icon>
