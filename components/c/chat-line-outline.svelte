<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuojq4b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tuojq4b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-line-outline" {...props}></Icon>
