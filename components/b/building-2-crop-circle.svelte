<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd8gkybdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pd8gkybdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:building-2-crop-circle" {...props}></Icon>
