<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc5hd6b6e.css';
import '../../css/i/iepl1qnjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc5hd6b6e"/><path class="iepl1qnjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:messages" {...props}></Icon>
