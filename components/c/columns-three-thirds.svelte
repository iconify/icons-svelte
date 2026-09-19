<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paejl3bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paejl3bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:columns-three-thirds" {...props}></Icon>
