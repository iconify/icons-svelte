<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz0jswbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lz0jswbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:phone-fill-arrow-up-right" {...props}></Icon>
