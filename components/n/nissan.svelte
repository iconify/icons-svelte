<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s41z-nbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s41z-nbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nissan" {...props}></Icon>
