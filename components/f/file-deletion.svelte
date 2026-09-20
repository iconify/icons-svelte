<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_1wi8_tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g_1wi8_tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:file-deletion" {...props}></Icon>
