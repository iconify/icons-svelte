<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjo89i77m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gjo89i77m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-right-square-fill" {...props}></Icon>
