<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uww1vyvgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uww1vyvgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:border-inside" {...props}></Icon>
