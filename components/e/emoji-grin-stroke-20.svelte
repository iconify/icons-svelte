<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo825-vwk.css';
import '../../css/z/zcqk8ssib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eo825-vwk"/><path class="zcqk8ssib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:emoji-grin-stroke-20" {...props}></Icon>
