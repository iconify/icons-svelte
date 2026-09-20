<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0me2lblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0me2lblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:book-unknown-filled" {...props}></Icon>
