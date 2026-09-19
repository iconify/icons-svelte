<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqs80qnxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fqs80qnxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:frowning-face-fill" {...props}></Icon>
