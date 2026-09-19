<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2cnbnb2l.css';
import '../../css/z/zbeas57fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y2cnbnb2l"/><path class="zbeas57fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:decreasefontsize" {...props}></Icon>
