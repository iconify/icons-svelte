<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btjoujb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btjoujb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-edit" {...props}></Icon>
