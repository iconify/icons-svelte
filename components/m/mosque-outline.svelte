<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_07cybpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e_07cybpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mosque-outline" {...props}></Icon>
