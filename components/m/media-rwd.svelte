<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sft8kxbtp.css';
import '../../css/e/eobk2uv8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sft8kxbtp"/><path clip-rule="evenodd" class="eobk2uv8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-rwd" {...props}></Icon>
