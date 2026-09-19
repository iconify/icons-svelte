<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlb12tben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vlb12tben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bubble-left-fill" {...props}></Icon>
