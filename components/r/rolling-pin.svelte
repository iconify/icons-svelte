<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4yh3zb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4yh3zb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:rolling-pin" {...props}></Icon>
