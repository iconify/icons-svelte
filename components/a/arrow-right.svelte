<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bapk_1f8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bapk_1f8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-right" {...props}></Icon>
