<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up8refqzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up8refqzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:frame-fill" {...props}></Icon>
