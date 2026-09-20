<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fge55pbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fge55pbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:desktop" {...props}></Icon>
