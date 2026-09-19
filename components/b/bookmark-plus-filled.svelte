<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la3to1btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la3to1btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-plus-filled" {...props}></Icon>
