<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utsk9mbdc.css';
import '../../css/a/a1wz2fbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="utsk9mbdc"/><path class="a1wz2fbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:photography-photo-image" {...props}></Icon>
