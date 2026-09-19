<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca-7h_wwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":771,"height":1024};
const content = `<path class="ca-7h_wwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:podium" {...props}></Icon>
