<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amo1dubnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amo1dubnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:person-walking-solid" {...props}></Icon>
