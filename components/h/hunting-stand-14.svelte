<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3fk4rlyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="v3fk4rlyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:hunting-stand-14" {...props}></Icon>
