<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfg_at6ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bfg_at6ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-bottom-right" {...props}></Icon>
