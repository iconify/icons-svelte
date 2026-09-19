<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lidfcs8vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lidfcs8vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:merge-horizontal" {...props}></Icon>
