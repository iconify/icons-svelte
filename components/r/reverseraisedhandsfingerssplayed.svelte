<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fex8l3b8p.css';
import '../../css/r/rw715wbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fex8l3b8p"/><path class="rw715wbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:reverseraisedhandsfingerssplayed" {...props}></Icon>
