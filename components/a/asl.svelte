<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgjvzrb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wgjvzrb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:asl" {...props}></Icon>
