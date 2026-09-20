<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxwy_hw-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oxwy_hw-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-cross-finger-heart" {...props}></Icon>
