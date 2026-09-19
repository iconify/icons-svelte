<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmvtqzacp.css';
import '../../css/a/a-jxqyhlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmvtqzacp"/><path class="a-jxqyhlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bible" {...props}></Icon>
