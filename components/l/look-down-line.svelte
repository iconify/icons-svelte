<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av0sy3bmo.css';
import '../../css/w/wli-clb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av0sy3bmo"/><path class="wli-clb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:look-down-line" {...props}></Icon>
