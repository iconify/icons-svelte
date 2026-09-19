<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4v37gz8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="g4v37gz8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grin-alt" {...props}></Icon>
