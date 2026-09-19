<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebl_hvbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ebl_hvbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-square-quote-fill" {...props}></Icon>
