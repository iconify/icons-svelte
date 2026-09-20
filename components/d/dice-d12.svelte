<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aca8y6bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aca8y6bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-d12" {...props}></Icon>
