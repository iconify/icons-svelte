<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-8zhzm_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w-8zhzm_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:paste-as-code" {...props}></Icon>
