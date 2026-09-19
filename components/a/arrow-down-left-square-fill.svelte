<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy0ndupne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xy0ndupne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-left-square-fill" {...props}></Icon>
