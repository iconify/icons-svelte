<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j34e_4brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j34e_4brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:golf-hole-bold" {...props}></Icon>
