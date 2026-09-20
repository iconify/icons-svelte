<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-7kan9kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u-7kan9kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bomb-solid" {...props}></Icon>
