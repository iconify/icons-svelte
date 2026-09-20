<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv30okbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uv30okbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:align-left" {...props}></Icon>
