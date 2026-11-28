<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9qyuw09p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9qyuw09p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:disc-solid" {...props}></Icon>
