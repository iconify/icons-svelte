<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frw9aro9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="frw9aro9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bold" {...props}></Icon>
