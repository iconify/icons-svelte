<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqkwdi4fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqkwdi4fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apache-kafka" {...props}></Icon>
