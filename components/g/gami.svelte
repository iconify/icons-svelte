<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqo6icbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqo6icbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gami" {...props}></Icon>
