<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrf6iq1zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrf6iq1zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cosine-wave" {...props}></Icon>
