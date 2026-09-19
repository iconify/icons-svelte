<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woup13bgg.css';
import '../../css/s/scdda8sqr.css';
import '../../css/q/qt8553dci.css';
import '../../css/d/dkcwfxbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="woup13bgg"/><path class="scdda8sqr"/><path class="qt8553dci"/><path class="dkcwfxbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:fish" {...props}></Icon>
