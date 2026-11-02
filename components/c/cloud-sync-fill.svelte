<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhghdrbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhghdrbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-sync-fill" {...props}></Icon>
