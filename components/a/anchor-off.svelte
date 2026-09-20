<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwqxh0d5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwqxh0d5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:anchor-off" {...props}></Icon>
