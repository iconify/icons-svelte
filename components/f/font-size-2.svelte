<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5-vskbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e5-vskbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:font-size-2" {...props}></Icon>
