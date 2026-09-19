<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah5v3fl3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ah5v3fl3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:repo-solid" {...props}></Icon>
