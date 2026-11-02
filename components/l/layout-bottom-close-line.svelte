<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd4zk4bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd4zk4bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-bottom-close-line" {...props}></Icon>
