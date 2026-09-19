<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2op-6baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s2op-6baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:attach" {...props}></Icon>
