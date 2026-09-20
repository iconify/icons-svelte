<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdlnd98sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xdlnd98sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:custom-feeds-like-favorite-solid" {...props}></Icon>
