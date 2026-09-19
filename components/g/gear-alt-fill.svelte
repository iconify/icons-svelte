<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt_ud7bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lt_ud7bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gear-alt-fill" {...props}></Icon>
