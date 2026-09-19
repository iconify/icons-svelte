<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm60-5ffo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dm60-5ffo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:fast-forward-one-five-x" {...props}></Icon>
