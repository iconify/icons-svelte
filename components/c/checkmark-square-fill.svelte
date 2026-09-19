<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo7c1d9kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uo7c1d9kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:checkmark-square-fill" {...props}></Icon>
