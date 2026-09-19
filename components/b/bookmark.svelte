<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz_v76b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cz_v76b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bookmark" {...props}></Icon>
