<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cslz_9bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cslz_9bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:justice-scale-2-remix" {...props}></Icon>
