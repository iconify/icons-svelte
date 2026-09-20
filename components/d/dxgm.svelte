<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1ct7n8ui.css';
import '../../css/d/dj56zmboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1ct7n8ui"/><path clip-rule="evenodd" class="dj56zmboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dxgm" {...props}></Icon>
