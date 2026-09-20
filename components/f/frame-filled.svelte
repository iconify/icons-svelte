<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3kw-3bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3kw-3bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:frame-filled" {...props}></Icon>
