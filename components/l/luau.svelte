<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd-9drfax.css';
import '../../css/j/j3pesbbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xd-9drfax"/><path class="j3pesbbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:luau" {...props}></Icon>
