<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh9yc8bel.css';
import '../../css/c/cvftmybtu.css';
import '../../css/a/a5p2lhbsw.css';
import '../../css/q/qu25mcb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh9yc8bel wm-k"/><path class="cvftmybtu wm-k"/><path class="a5p2lhbsw wm-a"/><path class="qu25mcb2l wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:history" {...props}></Icon>
