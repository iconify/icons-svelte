<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc7r3hb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc7r3hb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-search-solid" {...props}></Icon>
