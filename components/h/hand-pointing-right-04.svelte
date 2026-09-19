<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9a-vzbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9a-vzbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hand-pointing-right-04" {...props}></Icon>
