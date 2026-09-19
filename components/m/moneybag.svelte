<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxnzi-byq.css';
import '../../css/d/dmwskda3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxnzi-byq"/><path class="dmwskda3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:moneybag" {...props}></Icon>
