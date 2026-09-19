<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1cdg_y4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="h1cdg_y4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:f-cursive" {...props}></Icon>
