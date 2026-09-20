<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv017rgfy.css';
import '../../css/a/aefel7b-l.css';
import '../../css/a/a0ch81bxw.css';
import '../../css/w/w4-pptbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gv017rgfy"/><path class="aefel7b-l"/><path class="a0ch81bxw"/><path class="w4-pptbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lidbrainz-light" {...props}></Icon>
