<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6n7epy-m.css';
import '../../css/m/mexmngaav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6n7epy-m"/><path class="mexmngaav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:chevrons-right" {...props}></Icon>
