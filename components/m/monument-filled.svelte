<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwlt0zbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwlt0zbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:monument-filled" {...props}></Icon>
