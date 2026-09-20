<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnqtpl8nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnqtpl8nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:behance-fill" {...props}></Icon>
