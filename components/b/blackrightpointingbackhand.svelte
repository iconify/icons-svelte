<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtmkjzt7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wtmkjzt7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackrightpointingbackhand" {...props}></Icon>
