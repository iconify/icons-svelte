<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b40_ogsqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b40_ogsqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hard-drive-x" {...props}></Icon>
