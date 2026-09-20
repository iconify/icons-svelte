<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uchsqubpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="uchsqubpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:code-1" {...props}></Icon>
