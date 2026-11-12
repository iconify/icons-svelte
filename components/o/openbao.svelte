<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo6tgw96g.css';
import '../../css/a/a5hkwzb3n.css';
import '../../css/r/renh8_kgy.css';
import '../../css/b/bf-kbob7n.css';
import '../../css/s/saw-75b7p.css';
import '../../css/i/iu8_vibja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="jo6tgw96g"/><path class="a5hkwzb3n"/><path class="renh8_kgy"/><path class="bf-kbob7n"/><path class="saw-75b7p"/><path class="iu8_vibja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openbao" {...props}></Icon>
