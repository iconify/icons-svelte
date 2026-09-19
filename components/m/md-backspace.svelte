<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whodj8b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="whodj8b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-backspace" {...props}></Icon>
