<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw3a_1zej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sw3a_1zej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:crown" {...props}></Icon>
