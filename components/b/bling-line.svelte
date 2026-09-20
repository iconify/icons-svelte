<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrsuk5b6z.css';
import '../../css/s/s_3yk55iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrsuk5b6z"/><path class="s_3yk55iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bling-line" {...props}></Icon>
