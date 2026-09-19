<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czmczs_ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="czmczs_ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:music-albums" {...props}></Icon>
