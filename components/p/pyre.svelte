<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf9bi_bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gf9bi_bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pyre" {...props}></Icon>
