<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foesq3whf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="foesq3whf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-up-square" {...props}></Icon>
