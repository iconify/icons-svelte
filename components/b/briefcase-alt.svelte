<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfjixkv7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfjixkv7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:briefcase-alt" {...props}></Icon>
