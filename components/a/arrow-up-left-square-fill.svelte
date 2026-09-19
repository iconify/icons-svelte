<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zivfc9bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zivfc9bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-left-square-fill" {...props}></Icon>
