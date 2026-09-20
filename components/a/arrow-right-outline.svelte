<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zchu_4bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zchu_4bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-outline" {...props}></Icon>
