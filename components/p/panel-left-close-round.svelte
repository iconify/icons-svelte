<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvvzo3brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvvzo3brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-left-close-round" {...props}></Icon>
