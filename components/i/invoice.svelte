<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0m3lcb0w.css';
import '../../css/o/on5ils5mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0m3lcb0w"/><path class="on5ils5mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:invoice" {...props}></Icon>
