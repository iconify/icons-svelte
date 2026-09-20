<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw_5fktgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw_5fktgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-out-control-point-fill" {...props}></Icon>
