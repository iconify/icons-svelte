<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9lz_tuxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g9lz_tuxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:qand-a-mirror" {...props}></Icon>
