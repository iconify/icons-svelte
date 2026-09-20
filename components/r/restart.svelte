<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwk2mab9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwk2mab9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:restart" {...props}></Icon>
