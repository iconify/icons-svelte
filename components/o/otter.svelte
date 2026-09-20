<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng3tch7ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ng3tch7ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:otter" {...props}></Icon>
