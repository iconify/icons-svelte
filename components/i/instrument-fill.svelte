<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrtnir10g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrtnir10g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:instrument-fill" {...props}></Icon>
