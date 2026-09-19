<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8b6wcepg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p8b6wcepg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:gitkraken" {...props}></Icon>
