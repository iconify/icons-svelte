<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t14b_mbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="t14b_mbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:music-albums-fill" {...props}></Icon>
