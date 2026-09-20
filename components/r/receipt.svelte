<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijvu4ybpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijvu4ybpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:receipt" {...props}></Icon>
