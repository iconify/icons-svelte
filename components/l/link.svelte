<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu7nefmvr.css';
import '../../css/e/ea0a-8box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":12};
const content = `<path class="tu7nefmvr"/><path class="ea0a-8box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:link" {...props}></Icon>
