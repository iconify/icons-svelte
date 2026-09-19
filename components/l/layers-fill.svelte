<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck5r02b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ck5r02b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:layers-fill" {...props}></Icon>
