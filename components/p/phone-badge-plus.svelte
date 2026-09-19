<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su5hedbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="su5hedbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:phone-badge-plus" {...props}></Icon>
