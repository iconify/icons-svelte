<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko23__bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko23__bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-markdown-filled" {...props}></Icon>
