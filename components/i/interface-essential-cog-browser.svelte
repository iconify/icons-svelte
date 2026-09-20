<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z84met-5h.css';
import '../../css/n/nr3dqcmlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z84met-5h"/><path class="nr3dqcmlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-cog-browser" {...props}></Icon>
