<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnlxeq75i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnlxeq75i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:drapes-closed" {...props}></Icon>
