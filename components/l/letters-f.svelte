<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7t-5kbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7t-5kbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-f" {...props}></Icon>
