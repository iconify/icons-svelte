<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjy7yupxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjy7yupxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:backward-1" {...props}></Icon>
