<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z62y6x8ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z62y6x8ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:record" {...props}></Icon>
