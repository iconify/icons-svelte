<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoqiwp4op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uoqiwp4op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:regionalindicatorr" {...props}></Icon>
