<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cisxu6win.css';
import '../../css/j/jub3nhbzk.css';
import '../../css/m/mx3d42bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cisxu6win"/><path class="jub3nhbzk"/><path class="mx3d42bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:bitcoin" {...props}></Icon>
