<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl30c4zma.css';
import '../../css/n/nm-0yofzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl30c4zma"/><path class="nm-0yofzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-filled" {...props}></Icon>
