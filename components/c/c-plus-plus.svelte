<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqu6bebpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rqu6bebpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:c-plus-plus" {...props}></Icon>
