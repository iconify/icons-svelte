<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpzo9b7op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kpzo9b7op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:humidity-none" {...props}></Icon>
