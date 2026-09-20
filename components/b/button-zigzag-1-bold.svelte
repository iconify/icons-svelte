<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6xsxtkuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6xsxtkuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:button-zigzag-1-bold" {...props}></Icon>
