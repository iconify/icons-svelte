<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chto62blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="chto62blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-0" {...props}></Icon>
