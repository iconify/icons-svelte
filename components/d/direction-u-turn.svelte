<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmw-2dj0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mmw-2dj0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-u-turn" {...props}></Icon>
