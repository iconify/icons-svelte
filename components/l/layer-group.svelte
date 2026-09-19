<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9cvk473l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v9cvk473l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:layer-group" {...props}></Icon>
