<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf60akhnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sf60akhnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-skip-back-2" {...props}></Icon>
