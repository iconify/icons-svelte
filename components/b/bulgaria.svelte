<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj9cgxb4q.css';
import '../../css/w/wprsklb5k.css';
import '../../css/b/bupxdcvvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="rj9cgxb4q"/><path class="wprsklb5k"/><path class="bupxdcvvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:bulgaria" {...props}></Icon>
