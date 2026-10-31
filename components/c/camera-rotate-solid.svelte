<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_3k02bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_3k02bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:camera-rotate-solid" {...props}></Icon>
