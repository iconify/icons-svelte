<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hndkjgbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hndkjgbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googleadmob" {...props}></Icon>
