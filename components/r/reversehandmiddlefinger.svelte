<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkdcq5bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mkdcq5bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:reversehandmiddlefinger" {...props}></Icon>
