<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu5x9bbvk.css';
import '../../css/n/ndj5swlkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu5x9bbvk"/><path class="ndj5swlkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:phone-search-filled" {...props}></Icon>
