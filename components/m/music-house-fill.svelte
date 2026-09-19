<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg7u04blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vg7u04blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:music-house-fill" {...props}></Icon>
