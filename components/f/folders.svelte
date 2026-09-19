<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk2xqnyxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk2xqnyxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folders" {...props}></Icon>
