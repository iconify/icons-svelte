<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko7evacid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko7evacid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevron-right" {...props}></Icon>
