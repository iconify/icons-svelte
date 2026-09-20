<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpc-6mina.css';
import '../../css/x/xczq1jt6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lpc-6mina"/><path class="xczq1jt6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:horseshoes" {...props}></Icon>
