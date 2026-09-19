<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lempij0ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lempij0ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:play-filled-alt" {...props}></Icon>
