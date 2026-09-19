<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrks_obiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":718,"height":717};
const content = `<path class="wrks_obiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:move" {...props}></Icon>
