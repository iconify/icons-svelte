<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9t57bbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9t57bbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dislike" {...props}></Icon>
