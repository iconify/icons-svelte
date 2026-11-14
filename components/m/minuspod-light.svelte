<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj3bhgb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rj3bhgb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minuspod-light" {...props}></Icon>
