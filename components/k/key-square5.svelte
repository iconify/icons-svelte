<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdt_v0b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qdt_v0b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:key-square5" {...props}></Icon>
