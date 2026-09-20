<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a772m_d8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a772m_d8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-up-dashed-square-remix" {...props}></Icon>
