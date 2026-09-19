<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4r_6ibkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="v4r_6ibkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:dog" {...props}></Icon>
