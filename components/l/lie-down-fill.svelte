<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hycozmbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hycozmbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lie-down-fill" {...props}></Icon>
