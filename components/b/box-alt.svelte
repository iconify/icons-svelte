<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8ws_bxph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8ws_bxph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:box-alt" {...props}></Icon>
