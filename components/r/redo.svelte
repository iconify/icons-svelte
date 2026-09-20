<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loa53obtg.css';
import '../../css/k/kxhuiabhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loa53obtg"/><path class="kxhuiabhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:redo" {...props}></Icon>
