<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a53tm5d4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a53tm5d4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bootstrap" {...props}></Icon>
