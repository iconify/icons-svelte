<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx5km29gc.css';
import '../../css/u/ua3nsqb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx5km29gc"/><path class="ua3nsqb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-slide-left-and-right-filled" {...props}></Icon>
