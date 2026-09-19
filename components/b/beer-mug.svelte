<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb0epmb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hb0epmb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:beer-mug" {...props}></Icon>
