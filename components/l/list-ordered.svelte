<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3jt7lijj.css';
import '../../css/t/tl3piacvt.css';
import '../../css/z/zw5s43bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3jt7lijj wm-k"/><path class="tl3piacvt wm-a"/><path class="wm-a zw5s43bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:list-ordered" {...props}></Icon>
