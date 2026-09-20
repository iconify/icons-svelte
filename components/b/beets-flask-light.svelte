<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9hmh0b9g.css';
import '../../css/u/ujufagbba.css';
import '../../css/s/s8i3jsm2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="f9hmh0b9g"/><path class="ujufagbba"/><path class="s8i3jsm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beets-flask-light" {...props}></Icon>
