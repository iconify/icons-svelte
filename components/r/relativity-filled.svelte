<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgae07xbo.css';
import '../../css/r/rr7ezt0es.css';
import '../../css/x/xfjodpqdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgae07xbo"/><path class="rr7ezt0es"/><path class="xfjodpqdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:relativity-filled" {...props}></Icon>
